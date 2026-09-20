<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk0u-ybaf.css';
import '../../css/x/xekl2mwvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="pk0u-ybaf"/><path class="xekl2mwvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pagination" {...props}></Icon>
