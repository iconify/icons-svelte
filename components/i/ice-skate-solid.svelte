<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9_i5_b0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9_i5_b0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ice-skate-solid" {...props}></Icon>
