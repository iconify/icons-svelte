<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-md9ub0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="t-md9ub0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:crop" {...props}></Icon>
