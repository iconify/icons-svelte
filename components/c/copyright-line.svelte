<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-68ozbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-68ozbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:copyright-line" {...props}></Icon>
