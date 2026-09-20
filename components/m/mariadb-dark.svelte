<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg38qu8cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eg38qu8cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mariadb-dark" {...props}></Icon>
