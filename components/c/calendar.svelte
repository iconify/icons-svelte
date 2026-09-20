<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5489if1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b5489if1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:calendar" {...props}></Icon>
