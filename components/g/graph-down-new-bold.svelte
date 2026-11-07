<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w300pfpxc.css';
import '../../css/s/siai_tb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w300pfpxc"/><path class="siai_tb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:graph-down-new-bold" {...props}></Icon>
