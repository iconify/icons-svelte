<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb6wl9bmp.css';
import '../../css/t/tpmdsvwzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kb6wl9bmp"/><path class="tpmdsvwzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:chevron-circle-up-alt" {...props}></Icon>
