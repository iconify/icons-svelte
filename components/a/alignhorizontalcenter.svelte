<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdw4irbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="cdw4irbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:alignhorizontalcenter" {...props}></Icon>
