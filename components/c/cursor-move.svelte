<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tahznkn8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tahznkn8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:cursor-move" {...props}></Icon>
