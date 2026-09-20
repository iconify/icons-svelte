<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-ost6bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="r-ost6bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:graphcool" {...props}></Icon>
