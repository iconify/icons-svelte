<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvt8df90n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xvt8df90n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:dice-five" {...props}></Icon>
