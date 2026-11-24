<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlxa70wnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlxa70wnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:drafting-compass-filled" {...props}></Icon>
