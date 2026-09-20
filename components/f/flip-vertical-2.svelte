<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr95f2b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr95f2b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:flip-vertical-2" {...props}></Icon>
