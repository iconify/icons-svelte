<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlwjky5aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlwjky5aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chart-column-decreasing-solid" {...props}></Icon>
