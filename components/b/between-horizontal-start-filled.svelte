<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb8rxjbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb8rxjbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:between-horizontal-start-filled" {...props}></Icon>
