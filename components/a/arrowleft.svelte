<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z86gewc1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":690,"height":719};
const content = `<path class="z86gewc1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:arrowleft" {...props}></Icon>
