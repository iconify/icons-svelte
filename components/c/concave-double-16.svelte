<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4fn36r9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b4fn36r9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:concave-double-16" {...props}></Icon>
