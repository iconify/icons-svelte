<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uagq75bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uagq75bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:note-1" {...props}></Icon>
