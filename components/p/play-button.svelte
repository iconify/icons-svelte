<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cymmyqb3s.css';
import '../../css/f/f0d5hoc7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="cymmyqb3s"/><path class="f0d5hoc7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:play-button" {...props}></Icon>
