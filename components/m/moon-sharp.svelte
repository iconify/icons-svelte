<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzqpya2xq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzqpya2xq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:moon-sharp" {...props}></Icon>
