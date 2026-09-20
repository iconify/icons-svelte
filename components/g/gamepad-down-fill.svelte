<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeci21u8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="eeci21u8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-down-fill" {...props}></Icon>
