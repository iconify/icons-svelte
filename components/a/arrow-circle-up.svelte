<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e46-ry4zz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e46-ry4zz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:arrow-circle-up" {...props}></Icon>
