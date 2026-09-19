<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yosbkpi3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yosbkpi3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:rituals" {...props}></Icon>
