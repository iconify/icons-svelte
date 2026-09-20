<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chz_ygbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chz_ygbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-refresh-variant-outline" {...props}></Icon>
