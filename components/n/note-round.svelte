<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf2qb-bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cf2qb-bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-round" {...props}></Icon>
