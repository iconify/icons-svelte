<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr07mhbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr07mhbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:avocado-solid" {...props}></Icon>
