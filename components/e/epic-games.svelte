<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwu36wfvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uwu36wfvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:epic-games" {...props}></Icon>
