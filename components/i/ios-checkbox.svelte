<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st9mc6zjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="st9mc6zjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-checkbox" {...props}></Icon>
