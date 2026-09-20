<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azayl7bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azayl7bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:knife" {...props}></Icon>
