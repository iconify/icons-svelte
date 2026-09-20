<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm4f9d33i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="sm4f9d33i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-up" {...props}></Icon>
