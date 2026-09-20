<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slxj0bb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slxj0bb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-pos-refresh" {...props}></Icon>
