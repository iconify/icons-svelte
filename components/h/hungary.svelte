<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1x_6zbkv.css';
import '../../css/s/s4vfm1orq.css';
import '../../css/n/nm2s24x-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="d1x_6zbkv"/><path class="s4vfm1orq"/><path class="nm2s24x-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:hungary" {...props}></Icon>
