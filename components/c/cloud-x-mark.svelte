<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxna43buh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxna43buh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cloud-x-mark" {...props}></Icon>
