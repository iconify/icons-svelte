<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vphf7_9kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vphf7_9kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:keeper-light" {...props}></Icon>
