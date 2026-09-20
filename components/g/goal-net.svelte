<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/romase2xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="romase2xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:goal-net" {...props}></Icon>
