<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3yp2ac-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3yp2ac-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:circle-fading-arrow-up" {...props}></Icon>
