<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odb6au6vj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="odb6au6vj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-happy" {...props}></Icon>
