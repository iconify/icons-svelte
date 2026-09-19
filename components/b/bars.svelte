<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_n-ew7ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_n-ew7ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:bars" {...props}></Icon>
