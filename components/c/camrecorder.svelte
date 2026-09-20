<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzvdfk53z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bzvdfk53z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:camrecorder" {...props}></Icon>
