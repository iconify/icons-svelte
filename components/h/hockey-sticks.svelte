<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc8fqpbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc8fqpbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hockey-sticks" {...props}></Icon>
