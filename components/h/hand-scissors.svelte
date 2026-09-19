<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srjvx7b4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="srjvx7b4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hand-scissors" {...props}></Icon>
