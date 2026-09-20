<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqu5qwbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqu5qwbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:note-2" {...props}></Icon>
