<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-2-gdbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="o-2-gdbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:music" {...props}></Icon>
