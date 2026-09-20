<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu4l0sb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu4l0sb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:panel-bottom-inactive" {...props}></Icon>
