<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbddd627w.css';
import '../../css/p/pia7y9bjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbddd627w"/><path class="pia7y9bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:add-to-queue" {...props}></Icon>
