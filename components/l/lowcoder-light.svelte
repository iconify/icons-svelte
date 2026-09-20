<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tucwt5bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tucwt5bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lowcoder-light" {...props}></Icon>
