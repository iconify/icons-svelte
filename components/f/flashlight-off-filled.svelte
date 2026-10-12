<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7onacbub.css';
import '../../css/f/f6gjy-b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x7onacbub"/><path class="f6gjy-b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:flashlight-off-filled" {...props}></Icon>
