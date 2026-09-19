<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiesivb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="oiesivb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:face-rolling-eyes" {...props}></Icon>
