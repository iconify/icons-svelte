<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb6b0ugaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb6b0ugaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bar-chart-2-fill" {...props}></Icon>
