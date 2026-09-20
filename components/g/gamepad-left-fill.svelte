<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5fdbb3rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="f5fdbb3rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-left-fill" {...props}></Icon>
