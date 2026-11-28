<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vln3y5t7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vln3y5t7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-number-5-solid" {...props}></Icon>
