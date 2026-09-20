<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp8z5tbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yp8z5tbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-using-terminal-kiosk-with-dollar" {...props}></Icon>
