<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gos7t18ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gos7t18ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chinese-knot-fill" {...props}></Icon>
