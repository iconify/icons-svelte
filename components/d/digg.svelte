<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj7h6gphw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1280};
const content = `<path class="lj7h6gphw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:digg" {...props}></Icon>
