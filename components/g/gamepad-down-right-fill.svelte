<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvti2vw8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="xvti2vw8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-down-right-fill" {...props}></Icon>
