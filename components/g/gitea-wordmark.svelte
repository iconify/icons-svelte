<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz-b3xwif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dz-b3xwif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gitea-wordmark" {...props}></Icon>
