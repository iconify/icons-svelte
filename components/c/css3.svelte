<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5dznj9-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a5dznj9-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:css3" {...props}></Icon>
