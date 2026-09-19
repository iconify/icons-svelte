<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaa2vpbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="xaa2vpbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:homealt" {...props}></Icon>
