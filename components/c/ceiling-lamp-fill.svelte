<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_z_s6grm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_z_s6grm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ceiling-lamp-fill" {...props}></Icon>
