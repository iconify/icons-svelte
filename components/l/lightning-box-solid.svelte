<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0x8xlzqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s0x8xlzqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:lightning-box-solid" {...props}></Icon>
