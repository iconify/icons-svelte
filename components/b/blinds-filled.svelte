<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stdr-7bvd.css';
import '../../css/z/zt9l85bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stdr-7bvd"/><path class="zt9l85bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:blinds-filled" {...props}></Icon>
