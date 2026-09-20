<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8qk8_h2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d8qk8_h2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:clock" {...props}></Icon>
