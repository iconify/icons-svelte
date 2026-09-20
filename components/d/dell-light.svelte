<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byhqp1buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="byhqp1buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dell-light" {...props}></Icon>
