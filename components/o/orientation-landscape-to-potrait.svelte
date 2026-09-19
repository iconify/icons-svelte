<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nybo-p7sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nybo-p7sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:orientation-landscape-to-potrait" {...props}></Icon>
