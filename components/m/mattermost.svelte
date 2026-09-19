<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztzz4wb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ztzz4wb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:mattermost" {...props}></Icon>
