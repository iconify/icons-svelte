<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5rwgpn5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g5rwgpn5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fish-jumping-up-cascade" {...props}></Icon>
