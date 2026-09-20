<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edi2sub5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edi2sub5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-right-bold" {...props}></Icon>
