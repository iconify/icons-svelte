<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dodjpsu0u.css';
import '../../css/a/a3b73cb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dodjpsu0u"/><path class="a3b73cb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:flashlight-filled" {...props}></Icon>
