<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irauy12_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irauy12_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:check" {...props}></Icon>
