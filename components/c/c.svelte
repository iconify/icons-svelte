<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc7skwb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":507,"height":671};
const content = `<path class="oc7skwb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:c" {...props}></Icon>
