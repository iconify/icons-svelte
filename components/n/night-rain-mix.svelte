<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuklvzb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="wuklvzb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:night-rain-mix" {...props}></Icon>
