<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug6jb8s5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ug6jb8s5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:report-warning" {...props}></Icon>
