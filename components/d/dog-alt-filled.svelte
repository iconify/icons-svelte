<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ice-8pbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ice-8pbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dog-alt-filled" {...props}></Icon>
