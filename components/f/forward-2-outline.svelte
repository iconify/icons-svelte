<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpdf6sb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dpdf6sb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:forward-2-outline" {...props}></Icon>
