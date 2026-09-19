<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfm84o1-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="bfm84o1-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:hourglass" {...props}></Icon>
