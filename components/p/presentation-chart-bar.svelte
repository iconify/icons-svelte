<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md62t3byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md62t3byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:presentation-chart-bar" {...props}></Icon>
