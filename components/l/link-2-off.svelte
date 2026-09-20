<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knc2cvbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knc2cvbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:link-2-off" {...props}></Icon>
