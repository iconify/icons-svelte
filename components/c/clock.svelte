<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m27qgfj9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="m27qgfj9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:clock" {...props}></Icon>
