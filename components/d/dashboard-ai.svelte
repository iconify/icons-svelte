<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_og7xf3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_og7xf3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:dashboard-ai" {...props}></Icon>
