<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqb611gig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqb611gig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:angel-line" {...props}></Icon>
