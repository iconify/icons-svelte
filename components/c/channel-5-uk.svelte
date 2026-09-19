<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3rh6sb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3rh6sb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:channel-5-uk" {...props}></Icon>
