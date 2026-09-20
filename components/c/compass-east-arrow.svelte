<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewgx1ek3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ewgx1ek3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:compass-east-arrow" {...props}></Icon>
