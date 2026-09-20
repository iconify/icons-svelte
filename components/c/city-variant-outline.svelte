<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cty081fxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cty081fxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:city-variant-outline" {...props}></Icon>
