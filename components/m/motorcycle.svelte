<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgz6g14qr.css';
import '../../css/b/bwy1ik_nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":24};
const content = `<path class="wgz6g14qr"/><path class="bwy1ik_nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:motorcycle" {...props}></Icon>
