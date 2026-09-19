<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sasmg8j9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="sasmg8j9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:dice-three" {...props}></Icon>
