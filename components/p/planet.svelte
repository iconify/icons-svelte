<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gla-pjbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gla-pjbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:planet" {...props}></Icon>
