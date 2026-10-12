<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6ppvcf2u.css';
import '../../css/s/s_xabeb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6ppvcf2u"/><path class="s_xabeb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bow-arrow-filled" {...props}></Icon>
