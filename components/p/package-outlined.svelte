<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxbvi_4ka.css';
import '../../css/z/z2pque0vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxbvi_4ka"/><path class="z2pque0vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:package-outlined" {...props}></Icon>
