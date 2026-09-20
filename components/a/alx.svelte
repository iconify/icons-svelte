<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi2iq4b2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi2iq4b2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:alx" {...props}></Icon>
