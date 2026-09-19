<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7s6tsbkb.css';
import '../../css/i/ik4wy9jol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7s6tsbkb"/><path class="ik4wy9jol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:checkmark-square-2-outline" {...props}></Icon>
