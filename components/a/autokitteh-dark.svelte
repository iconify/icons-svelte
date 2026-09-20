<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te8lzdv-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="te8lzdv-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:autokitteh-dark" {...props}></Icon>
