<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdrt19kgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdrt19kgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:book-star" {...props}></Icon>
