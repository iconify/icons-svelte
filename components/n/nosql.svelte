<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsv6otbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hsv6otbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:nosql" {...props}></Icon>
