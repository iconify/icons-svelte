<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4pj5jbdc.css';
import '../../css/i/in5wtwq8h.css';
import '../../css/f/f2smzy9kb.css';
import '../../css/e/e4zfowz9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" class="u4pj5jbdc"/><path class="in5wtwq8h"/><path class="f2smzy9kb"/><path class="e4zfowz9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:cl-button" {...props}></Icon>
