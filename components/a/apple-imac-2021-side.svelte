<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpp35q0pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpp35q0pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:apple-imac-2021-side" {...props}></Icon>
