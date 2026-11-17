<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aczw4yb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aczw4yb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrows-to-axis-horizontal" {...props}></Icon>
