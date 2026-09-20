<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv92jsiur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uv92jsiur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-contacts-dark" {...props}></Icon>
