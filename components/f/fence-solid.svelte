<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5cmc0r-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5cmc0r-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:fence-solid" {...props}></Icon>
