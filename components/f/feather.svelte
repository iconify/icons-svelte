<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf-c07bjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hf-c07bjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:feather" {...props}></Icon>
