<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qooepw9_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qooepw9_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:buy-me-a-coffee-dark" {...props}></Icon>
