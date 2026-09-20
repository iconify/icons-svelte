<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-e16ub1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-e16ub1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dog-line" {...props}></Icon>
