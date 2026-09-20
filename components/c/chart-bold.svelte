<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqef07b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqef07b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chart-bold" {...props}></Icon>
