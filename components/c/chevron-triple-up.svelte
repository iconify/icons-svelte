<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzo0wjp8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzo0wjp8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-triple-up" {...props}></Icon>
