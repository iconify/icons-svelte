<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuyudz.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-76.css';
import '../../css/f/fill-to-0_3.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xuyudz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:bluesky-twotone" {...props}></Icon>
