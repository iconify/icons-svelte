<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8ct4wbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x8ct4wbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:bubble" {...props}></Icon>
