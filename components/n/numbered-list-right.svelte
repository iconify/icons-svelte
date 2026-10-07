<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_fy5w18b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_fy5w18b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:numbered-list-right" {...props}></Icon>
