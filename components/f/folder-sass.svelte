<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqup61b4d.css';
import '../../css/r/rr671wplb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oqup61b4d"/><path class="rr671wplb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-sass" {...props}></Icon>
