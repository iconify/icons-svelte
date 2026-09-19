<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdc_7m84r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdc_7m84r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:currency-rupee" {...props}></Icon>
