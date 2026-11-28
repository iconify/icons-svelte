<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_g3i6r_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_g3i6r_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-solid" {...props}></Icon>
