<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pth7mvs2w.css';
import '../../css/f/ff9jhsbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pth7mvs2w"/><rect class="ff9jhsbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:lock-closed-outline" {...props}></Icon>
