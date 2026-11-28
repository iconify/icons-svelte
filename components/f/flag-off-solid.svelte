<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-c0-2jci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-c0-2jci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flag-off-solid" {...props}></Icon>
