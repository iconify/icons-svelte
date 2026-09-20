<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrax7kfye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qrax7kfye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:moustache-flat" {...props}></Icon>
