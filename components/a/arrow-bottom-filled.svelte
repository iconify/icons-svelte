<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds9m95fda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds9m95fda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-bottom-filled" {...props}></Icon>
