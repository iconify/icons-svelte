<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1eaz_cjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1eaz_cjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-text-arrow-right-outline" {...props}></Icon>
