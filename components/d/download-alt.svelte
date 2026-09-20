<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6brtmb2k.css';
import '../../css/p/p-2h8ebhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6brtmb2k"/><path class="p-2h8ebhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:download-alt" {...props}></Icon>
