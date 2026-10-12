<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgw916bkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgw916bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:globe-filled" {...props}></Icon>
