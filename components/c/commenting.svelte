<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqmfhq6dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cqmfhq6dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:commenting" {...props}></Icon>
