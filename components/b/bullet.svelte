<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6spqrlet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6spqrlet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bullet" {...props}></Icon>
