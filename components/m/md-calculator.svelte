<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m12m9vb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m12m9vb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-calculator" {...props}></Icon>
