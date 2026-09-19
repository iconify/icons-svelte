<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm9c_ib7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":401,"height":512};
const content = `<path class="hm9c_ib7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:bintray" {...props}></Icon>
