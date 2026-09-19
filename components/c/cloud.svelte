<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpiu6lnbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":730,"height":710};
const content = `<path class="mpiu6lnbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:cloud" {...props}></Icon>
