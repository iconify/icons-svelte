<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lixhw-b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lixhw-b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mashable" {...props}></Icon>
