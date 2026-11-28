<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_-0hib6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_-0hib6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:avocado" {...props}></Icon>
