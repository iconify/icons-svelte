<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqhvr3bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1360,"height":1000};
const content = `<path class="hqhvr3bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:mail" {...props}></Icon>
