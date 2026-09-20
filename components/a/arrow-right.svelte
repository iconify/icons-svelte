<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg566bbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg566bbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-right" {...props}></Icon>
