<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_o07-b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_o07-b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:code-block" {...props}></Icon>
