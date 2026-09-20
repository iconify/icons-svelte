<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ake4l8bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ake4l8bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:minus-12" {...props}></Icon>
