<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw8ytabjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="lw8ytabjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:chart" {...props}></Icon>
