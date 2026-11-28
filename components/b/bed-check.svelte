<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcw-0tbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcw-0tbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bed-check" {...props}></Icon>
