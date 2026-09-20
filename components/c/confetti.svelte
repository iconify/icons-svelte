<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4jj9-bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4jj9-bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:confetti" {...props}></Icon>
