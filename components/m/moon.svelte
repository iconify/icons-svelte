<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjgvwccwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjgvwccwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:moon" {...props}></Icon>
