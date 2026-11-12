<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exvhc09yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="exvhc09yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:irs-light" {...props}></Icon>
