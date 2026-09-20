<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilkm3-gfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilkm3-gfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-long-up-right" {...props}></Icon>
