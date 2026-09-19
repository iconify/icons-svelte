<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2ikby-aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="s2ikby-aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file" {...props}></Icon>
