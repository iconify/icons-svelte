<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6mvl4wxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r6mvl4wxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ev-charge" {...props}></Icon>
