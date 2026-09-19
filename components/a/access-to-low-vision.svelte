<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldkpy_bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldkpy_bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:access-to-low-vision" {...props}></Icon>
