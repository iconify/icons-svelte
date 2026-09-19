<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izu-4o1ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izu-4o1ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:cheese-outline" {...props}></Icon>
