<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anjx8r53q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="anjx8r53q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:info" {...props}></Icon>
