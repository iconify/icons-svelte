<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br0fl3byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br0fl3byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:nodejs" {...props}></Icon>
