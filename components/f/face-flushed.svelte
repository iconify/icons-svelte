<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezg5edd7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ezg5edd7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:face-flushed" {...props}></Icon>
