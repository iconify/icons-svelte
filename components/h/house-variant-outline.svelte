<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsmf9jbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsmf9jbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-variant-outline" {...props}></Icon>
