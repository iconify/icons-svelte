<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg8x53b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg8x53b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:collapse-vertical-line" {...props}></Icon>
