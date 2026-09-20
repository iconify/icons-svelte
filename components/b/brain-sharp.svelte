<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy460lbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uy460lbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:brain-sharp" {...props}></Icon>
