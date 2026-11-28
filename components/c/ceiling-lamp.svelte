<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lffg11dkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lffg11dkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:ceiling-lamp" {...props}></Icon>
