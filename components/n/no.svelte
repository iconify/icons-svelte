<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2xgv55tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y2xgv55tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:no" {...props}></Icon>
