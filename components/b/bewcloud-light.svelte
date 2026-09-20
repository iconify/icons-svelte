<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzv93wbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uzv93wbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bewcloud-light" {...props}></Icon>
