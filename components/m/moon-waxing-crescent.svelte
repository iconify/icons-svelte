<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1njp3l4b.css';
import '../../css/m/md6xbkbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v1njp3l4b"/><path class="md6xbkbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:moon-waxing-crescent" {...props}></Icon>
