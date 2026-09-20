<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edonqwbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edonqwbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:edge-legacy" {...props}></Icon>
