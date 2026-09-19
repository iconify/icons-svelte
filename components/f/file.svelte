<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6c7ln5ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":560,"height":850};
const content = `<path class="f6c7ln5ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:file" {...props}></Icon>
