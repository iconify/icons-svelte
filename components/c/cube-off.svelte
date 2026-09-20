<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzwhspbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzwhspbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cube-off" {...props}></Icon>
