<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3yj7wbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y3yj7wbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:oat-2" {...props}></Icon>
