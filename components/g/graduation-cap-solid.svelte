<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1b0bxvnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1b0bxvnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:graduation-cap-solid" {...props}></Icon>
