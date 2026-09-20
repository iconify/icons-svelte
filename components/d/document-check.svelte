<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flslc_b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flslc_b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:document-check" {...props}></Icon>
