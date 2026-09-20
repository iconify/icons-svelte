<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veuj-zb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="veuj-zb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-laboratory" {...props}></Icon>
