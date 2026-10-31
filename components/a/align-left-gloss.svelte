<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_4r47cdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_4r47cdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:align-left-gloss" {...props}></Icon>
