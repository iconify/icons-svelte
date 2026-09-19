<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrh4tzs5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="qrh4tzs5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:lira-sign" {...props}></Icon>
