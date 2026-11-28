<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfm6tob8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary rfm6tob8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bed-bunk-duotone" {...props}></Icon>
