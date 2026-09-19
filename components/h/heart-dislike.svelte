<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmmf48b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bmmf48b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:heart-dislike" {...props}></Icon>
