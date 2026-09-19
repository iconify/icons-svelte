<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr6shkb4z.css';
import '../../css/p/p11_xsbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr6shkb4z"/><path class="p11_xsbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ghost" {...props}></Icon>
