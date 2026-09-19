<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsg-6dv6p.css';
import '../../css/q/quljz8buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsg-6dv6p"/><path class="quljz8buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-user-account" {...props}></Icon>
