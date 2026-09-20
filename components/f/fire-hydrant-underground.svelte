<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eli7y2biq.css';
import '../../css/p/pb5i8-bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eli7y2biq"/><path class="pb5i8-bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:fire-hydrant-underground" {...props}></Icon>
