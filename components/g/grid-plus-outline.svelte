<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg_xm2btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xg_xm2btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:grid-plus-outline" {...props}></Icon>
