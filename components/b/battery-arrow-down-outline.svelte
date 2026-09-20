<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzdg_bqbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzdg_bqbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-arrow-down-outline" {...props}></Icon>
