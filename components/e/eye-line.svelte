<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcauk966l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcauk966l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:eye-line" {...props}></Icon>
