<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5zlcr8ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="j5zlcr8ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-right-fill" {...props}></Icon>
