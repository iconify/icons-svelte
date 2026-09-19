<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzs9lxbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yzs9lxbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:prestashop-wordmark" {...props}></Icon>
