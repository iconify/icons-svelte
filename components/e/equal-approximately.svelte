<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnyd-ab1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnyd-ab1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:equal-approximately" {...props}></Icon>
