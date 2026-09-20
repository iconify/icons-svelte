<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru9wcp0zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru9wcp0zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ink-percent-alert" {...props}></Icon>
