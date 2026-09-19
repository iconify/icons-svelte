<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5z1hnb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r5z1hnb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-create" {...props}></Icon>
