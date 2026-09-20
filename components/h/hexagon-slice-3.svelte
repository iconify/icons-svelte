<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrmvrvlle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrmvrvlle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hexagon-slice-3" {...props}></Icon>
