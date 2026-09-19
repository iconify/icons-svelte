<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx6re6bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gx6re6bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-arrow-back" {...props}></Icon>
