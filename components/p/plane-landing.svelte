<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_j61dk-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_j61dk-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:plane-landing" {...props}></Icon>
