<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8j3sfweg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y8j3sfweg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homebridge-dark" {...props}></Icon>
