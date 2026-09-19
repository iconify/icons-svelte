<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjp48nbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="yjp48nbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:obp" {...props}></Icon>
