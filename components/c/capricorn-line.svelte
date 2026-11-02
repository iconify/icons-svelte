<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql2n6wb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql2n6wb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:capricorn-line" {...props}></Icon>
