<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehxy3fbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":224,"height":472};
const content = `<path class="ehxy3fbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:play" {...props}></Icon>
