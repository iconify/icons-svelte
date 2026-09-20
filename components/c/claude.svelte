<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk8bvthsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="gk8bvthsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:claude" {...props}></Icon>
