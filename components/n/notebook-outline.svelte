<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylt-5-b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylt-5-b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:notebook-outline" {...props}></Icon>
