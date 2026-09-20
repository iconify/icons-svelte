<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peayf_bwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="peayf_bwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hail-taxi" {...props}></Icon>
