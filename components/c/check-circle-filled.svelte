<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1gmc4l8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1gmc4l8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:check-circle-filled" {...props}></Icon>
