<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k56p0xzaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k56p0xzaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:achievement-variant" {...props}></Icon>
