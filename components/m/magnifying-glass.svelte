<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc2z0-6oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vc2z0-6oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:magnifying-glass" {...props}></Icon>
