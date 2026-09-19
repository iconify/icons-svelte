<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po20zu72v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="po20zu72v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:left-long" {...props}></Icon>
