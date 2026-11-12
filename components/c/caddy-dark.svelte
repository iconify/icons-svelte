<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpdkwn6lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mpdkwn6lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:caddy-dark" {...props}></Icon>
