<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1yarxbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1yarxbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:adjustments-vertical-solid" {...props}></Icon>
