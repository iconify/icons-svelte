<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wksg6tbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="wksg6tbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-fill" {...props}></Icon>
