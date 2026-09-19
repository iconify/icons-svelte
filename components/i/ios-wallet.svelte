<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wejjyi8fq.css';
import '../../css/i/im3c3rjxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wejjyi8fq"/><path class="im3c3rjxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-wallet" {...props}></Icon>
