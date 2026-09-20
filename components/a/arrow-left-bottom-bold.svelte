<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umd0n7wwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umd0n7wwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-left-bottom-bold" {...props}></Icon>
