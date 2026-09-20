<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok4r3opti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ok4r3opti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:music" {...props}></Icon>
