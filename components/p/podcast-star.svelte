<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-v5hsceh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-v5hsceh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:podcast-star" {...props}></Icon>
