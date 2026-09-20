<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbr937byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbr937byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:location-off" {...props}></Icon>
