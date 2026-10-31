<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4s20ps9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4s20ps9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plus-round" {...props}></Icon>
