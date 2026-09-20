<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1iud0s8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h1iud0s8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:namur-out-of-spec" {...props}></Icon>
