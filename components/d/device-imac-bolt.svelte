<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh6ydbb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh6ydbb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-bolt" {...props}></Icon>
