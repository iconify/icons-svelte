<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en1zvri8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="en1zvri8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:lilypond" {...props}></Icon>
