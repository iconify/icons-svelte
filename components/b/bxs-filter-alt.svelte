<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epojvw4sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epojvw4sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-filter-alt" {...props}></Icon>
