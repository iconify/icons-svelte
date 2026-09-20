<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldnmay76x.css';
import '../../css/i/in5wtwq8h.css';
import '../../css/q/qufqqzb5y.css';
import '../../css/e/e4zfowz9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" class="ldnmay76x"/><path class="in5wtwq8h"/><path clip-rule="evenodd" class="qufqqzb5y"/><path class="e4zfowz9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:o-button-blood-type" {...props}></Icon>
