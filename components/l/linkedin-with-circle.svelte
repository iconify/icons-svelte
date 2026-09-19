<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpgdi0v8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xpgdi0v8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:linkedin-with-circle" {...props}></Icon>
