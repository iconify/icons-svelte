<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jstqmr1bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jstqmr1bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:film-heart" {...props}></Icon>
