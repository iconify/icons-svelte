<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vog_o-bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vog_o-bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:medkit" {...props}></Icon>
