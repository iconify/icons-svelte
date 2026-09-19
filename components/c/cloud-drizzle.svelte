<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxmh1e_dh.css';
import '../../css/n/np-r86b3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxmh1e_dh"/><path class="np-r86b3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:cloud-drizzle" {...props}></Icon>
