<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcvv1xbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":20};
const content = `<path class="rcvv1xbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:discord" {...props}></Icon>
