<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cno3tnb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cno3tnb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-right-up-long-fill" {...props}></Icon>
