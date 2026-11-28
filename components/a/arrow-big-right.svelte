<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh88yjbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh88yjbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:arrow-big-right" {...props}></Icon>
