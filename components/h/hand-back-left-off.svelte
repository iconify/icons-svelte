<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhct0z40r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhct0z40r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-back-left-off" {...props}></Icon>
