<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyezpzb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyezpzb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-down-right-solid" {...props}></Icon>
