<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4s6-81zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r4s6-81zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:prisma" {...props}></Icon>
