<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/airbmyclf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="airbmyclf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bar-chart-box-fill" {...props}></Icon>
