<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc_3xnmin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vc_3xnmin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:markdownlint" {...props}></Icon>
