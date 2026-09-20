<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm-5iib6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm-5iib6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-path-single-counterclockwise-solid" {...props}></Icon>
