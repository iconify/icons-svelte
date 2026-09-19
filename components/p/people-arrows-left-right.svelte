<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8w70vxyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="s8w70vxyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:people-arrows-left-right" {...props}></Icon>
