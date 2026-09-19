<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtvrf6dgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtvrf6dgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:github" {...props}></Icon>
