<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3uv8ueym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3uv8ueym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:book-open-plus" {...props}></Icon>
