<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5qx8cb0r.css';
import '../../css/a/aycg7s_1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="h5qx8cb0r"/><path class="aycg7s_1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:dribbble" {...props}></Icon>
