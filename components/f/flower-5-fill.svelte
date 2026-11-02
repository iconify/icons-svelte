<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx8_68b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx8_68b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flower-5-fill" {...props}></Icon>
