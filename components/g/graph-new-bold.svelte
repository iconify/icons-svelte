<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri62nr2ps.css';
import '../../css/s/siai_tb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ri62nr2ps"/><path class="siai_tb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:graph-new-bold" {...props}></Icon>
