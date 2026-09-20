<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5u27ab7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5u27ab7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bell" {...props}></Icon>
