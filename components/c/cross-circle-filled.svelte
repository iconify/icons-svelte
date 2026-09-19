<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2nfbtbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2nfbtbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cross-circle-filled" {...props}></Icon>
