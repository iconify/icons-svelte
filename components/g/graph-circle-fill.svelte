<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtr9hcbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="wtr9hcbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:graph-circle-fill" {...props}></Icon>
