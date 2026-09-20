<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx6k5mdai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vx6k5mdai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:globe-alt" {...props}></Icon>
