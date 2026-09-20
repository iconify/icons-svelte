<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9-abobfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j9-abobfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:energy" {...props}></Icon>
