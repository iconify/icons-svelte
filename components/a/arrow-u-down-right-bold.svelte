<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe8s97qji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe8s97qji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-u-down-right-bold" {...props}></Icon>
