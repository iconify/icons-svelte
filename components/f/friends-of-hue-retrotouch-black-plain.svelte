<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drlghjk_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drlghjk_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:friends-of-hue-retrotouch-black-plain" {...props}></Icon>
