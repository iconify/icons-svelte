<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv78f6y5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv78f6y5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ampersands-fill" {...props}></Icon>
