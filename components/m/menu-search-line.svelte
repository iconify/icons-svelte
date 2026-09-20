<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqie0rbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqie0rbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-search-line" {...props}></Icon>
