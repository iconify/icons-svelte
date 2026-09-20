<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0d37kbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e0d37kbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:bicycle-structure" {...props}></Icon>
