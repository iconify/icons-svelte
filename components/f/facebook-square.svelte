<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je9v0ja6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="je9v0ja6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:facebook-square" {...props}></Icon>
