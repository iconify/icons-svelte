<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktxbgbbpn.css';
import '../../css/y/y3f_nfkuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktxbgbbpn"/><path class="y3f_nfkuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:intellect" {...props}></Icon>
