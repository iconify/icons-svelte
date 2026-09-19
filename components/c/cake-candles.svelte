<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osf5v3bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="osf5v3bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cake-candles" {...props}></Icon>
