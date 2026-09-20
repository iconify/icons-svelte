<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtfe-5bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vtfe-5bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:navidrome-light" {...props}></Icon>
