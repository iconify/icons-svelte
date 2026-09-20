<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-pfo7vby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="y-pfo7vby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:helicopter" {...props}></Icon>
