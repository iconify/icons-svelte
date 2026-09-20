<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5zlxkrxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m5zlxkrxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronics-tape-cassette" {...props}></Icon>
