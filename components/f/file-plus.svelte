<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le1knnbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="le1knnbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:file-plus" {...props}></Icon>
