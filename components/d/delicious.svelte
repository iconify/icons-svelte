<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhie0q3xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rhie0q3xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:delicious" {...props}></Icon>
