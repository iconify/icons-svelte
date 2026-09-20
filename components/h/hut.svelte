<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5s43x33f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l5s43x33f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:hut" {...props}></Icon>
