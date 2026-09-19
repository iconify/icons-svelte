<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz2vv8csr.css';
import '../../css/z/z0s8mnbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kz2vv8csr"/><path class="z0s8mnbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-narrow-wide-filled" {...props}></Icon>
