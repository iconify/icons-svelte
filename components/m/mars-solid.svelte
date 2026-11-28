<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg-tfrb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg-tfrb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mars-solid" {...props}></Icon>
