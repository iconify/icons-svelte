<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_xl-jo9w.css';
import '../../css/d/d46rroheb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="f_xl-jo9w"/><path class="d46rroheb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:box" {...props}></Icon>
