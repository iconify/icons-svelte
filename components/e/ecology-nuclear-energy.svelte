<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk7rcacre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uk7rcacre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:ecology-nuclear-energy" {...props}></Icon>
