<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjppjp8yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjppjp8yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:hiking" {...props}></Icon>
