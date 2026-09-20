<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpqxt4psy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="xpqxt4psy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-down-right" {...props}></Icon>
