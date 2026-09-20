<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_vyfibua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h_vyfibua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:design-color-painting-palette" {...props}></Icon>
