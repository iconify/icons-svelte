<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rog1hobvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rog1hobvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:asciidoc" {...props}></Icon>
