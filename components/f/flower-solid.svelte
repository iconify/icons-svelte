<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5q4qsvke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5q4qsvke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flower-solid" {...props}></Icon>
