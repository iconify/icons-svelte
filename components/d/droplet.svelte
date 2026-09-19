<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8ct_fb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8ct_fb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:droplet" {...props}></Icon>
