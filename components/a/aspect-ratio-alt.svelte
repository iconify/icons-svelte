<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us8wt9b6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="us8wt9b6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:aspect-ratio-alt" {...props}></Icon>
