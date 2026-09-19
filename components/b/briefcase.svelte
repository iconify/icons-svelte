<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6013-iew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b6013-iew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:briefcase" {...props}></Icon>
