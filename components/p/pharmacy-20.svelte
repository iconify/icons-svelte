<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfxffib8l.css';
import '../../css/w/we7578b5j.css';
import '../../css/q/qpludsmxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kfxffib8l"/><path class="we7578b5j"/><path class="qpludsmxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pharmacy-20" {...props}></Icon>
