<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al3jz0dfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="al3jz0dfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pinwheel-2-line" {...props}></Icon>
