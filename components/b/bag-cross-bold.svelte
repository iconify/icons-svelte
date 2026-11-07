<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrpl2sb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xrpl2sb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-cross-bold" {...props}></Icon>
