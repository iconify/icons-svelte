<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw6l7tbdq.css';
import '../../css/d/dzjiyss3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fw6l7tbdq"/><path class="dzjiyss3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:golf-cart" {...props}></Icon>
