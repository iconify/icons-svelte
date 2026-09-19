<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9xue-bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="p9xue-bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:handswipe" {...props}></Icon>
