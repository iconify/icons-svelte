<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd9l58i1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd9l58i1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bar-code-01" {...props}></Icon>
