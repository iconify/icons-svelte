<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uak386bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uak386bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:circle-stop" {...props}></Icon>
