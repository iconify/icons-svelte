<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-cte0bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-cte0bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:globe-line" {...props}></Icon>
