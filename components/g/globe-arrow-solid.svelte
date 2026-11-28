<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oohom20oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oohom20oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:globe-arrow-solid" {...props}></Icon>
