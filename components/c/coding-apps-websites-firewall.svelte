<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkwgcubuy.css';
import '../../css/o/ostcmkorl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kkwgcubuy"/><path class="ostcmkorl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:coding-apps-websites-firewall" {...props}></Icon>
