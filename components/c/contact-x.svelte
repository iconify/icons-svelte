<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrr1d9bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrr1d9bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:contact-x" {...props}></Icon>
