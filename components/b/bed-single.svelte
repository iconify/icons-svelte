<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0q3nyf6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0q3nyf6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bed-single" {...props}></Icon>
