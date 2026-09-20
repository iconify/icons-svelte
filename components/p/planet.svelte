<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylfm_3b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylfm_3b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:planet" {...props}></Icon>
