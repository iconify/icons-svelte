<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyuu4fy-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyuu4fy-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:diko" {...props}></Icon>
