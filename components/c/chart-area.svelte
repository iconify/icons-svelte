<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol1j8y3wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ol1j8y3wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:chart-area" {...props}></Icon>
