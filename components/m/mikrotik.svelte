<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynqd7wbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ynqd7wbwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mikrotik" {...props}></Icon>
