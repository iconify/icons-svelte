<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w968xs1ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w968xs1ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-divide-solid" {...props}></Icon>
