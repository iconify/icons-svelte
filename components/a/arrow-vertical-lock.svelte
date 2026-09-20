<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx_0q1bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx_0q1bgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-vertical-lock" {...props}></Icon>
