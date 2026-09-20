<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp2h1tbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rp2h1tbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:align-vertical" {...props}></Icon>
