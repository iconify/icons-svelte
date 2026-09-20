<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7jb9-9qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l7jb9-9qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:power-transformer" {...props}></Icon>
