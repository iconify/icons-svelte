<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q09r_w8dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q09r_w8dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:headset-help" {...props}></Icon>
