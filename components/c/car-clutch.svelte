<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggzqh9biz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggzqh9biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-clutch" {...props}></Icon>
