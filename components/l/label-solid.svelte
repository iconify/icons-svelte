<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzd_zbc2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzd_zbc2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:label-solid" {...props}></Icon>
