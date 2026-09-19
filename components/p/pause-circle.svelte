<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz83p3b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xz83p3b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:pause-circle" {...props}></Icon>
