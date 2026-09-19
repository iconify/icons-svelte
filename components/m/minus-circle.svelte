<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxan9g_6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="qxan9g_6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:minus-circle" {...props}></Icon>
