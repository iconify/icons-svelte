<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd-6dbc8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="sd-6dbc8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:fire-burner" {...props}></Icon>
