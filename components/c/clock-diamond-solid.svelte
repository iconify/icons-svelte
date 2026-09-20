<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtn7h2b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtn7h2b2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:clock-diamond-solid" {...props}></Icon>
