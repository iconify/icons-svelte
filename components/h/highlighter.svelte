<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc557gbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fc557gbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:highlighter" {...props}></Icon>
