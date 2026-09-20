<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfx0_2f9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qfx0_2f9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dice-two-solid" {...props}></Icon>
