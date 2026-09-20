<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnq2l7byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnq2l7byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:crosshair-line" {...props}></Icon>
