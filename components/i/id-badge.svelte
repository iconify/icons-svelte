<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g81rw9b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="g81rw9b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:id-badge" {...props}></Icon>
