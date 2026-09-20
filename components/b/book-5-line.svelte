<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg14hfbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg14hfbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-5-line" {...props}></Icon>
