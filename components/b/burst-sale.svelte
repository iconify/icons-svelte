<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3t2mwhtg.css';
import '../../css/c/ckjmv4bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="l3t2mwhtg"/><path class="ckjmv4bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:burst-sale" {...props}></Icon>
