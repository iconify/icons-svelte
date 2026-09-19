<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a10l0tb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a10l0tb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:play-fill" {...props}></Icon>
