<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc4k0s5gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc4k0s5gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flight-land-fill" {...props}></Icon>
