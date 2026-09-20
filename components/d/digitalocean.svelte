<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dla8w8bon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dla8w8bon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:digitalocean" {...props}></Icon>
