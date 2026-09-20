<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toypk4f0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="toypk4f0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:fire-hydrant" {...props}></Icon>
