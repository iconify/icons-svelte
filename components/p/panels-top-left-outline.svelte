<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acs2urb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="acs2urb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panels-top-left-outline" {...props}></Icon>
