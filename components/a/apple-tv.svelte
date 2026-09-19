<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc-k9xb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc-k9xb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:apple-tv" {...props}></Icon>
