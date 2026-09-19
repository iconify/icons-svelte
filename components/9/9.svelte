<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsf0zp73a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="nsf0zp73a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:9" {...props}></Icon>
