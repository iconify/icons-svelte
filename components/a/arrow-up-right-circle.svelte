<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag_fw_b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ag_fw_b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-up-right-circle" {...props}></Icon>
