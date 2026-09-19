<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2fefybui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":672};
const content = `<path class="x2fefybui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:login" {...props}></Icon>
