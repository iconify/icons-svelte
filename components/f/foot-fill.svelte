<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3y9vxbhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3y9vxbhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:foot-fill" {...props}></Icon>
