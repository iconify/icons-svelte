<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc4jqtbfv.css';
import '../../css/n/nt_tpccog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pc4jqtbfv"/><path class="nt_tpccog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:playlist-bold" {...props}></Icon>
