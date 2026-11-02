<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muxnp-srw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muxnp-srw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:parentheses-line" {...props}></Icon>
