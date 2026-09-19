<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k59jp2z-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k59jp2z-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:house-close" {...props}></Icon>
