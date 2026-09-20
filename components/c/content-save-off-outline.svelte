<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ull9gzb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ull9gzb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:content-save-off-outline" {...props}></Icon>
