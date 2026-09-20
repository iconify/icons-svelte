<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxfjaebts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxfjaebts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:laptop-expressive" {...props}></Icon>
