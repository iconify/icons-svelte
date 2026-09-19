<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzi66zbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzi66zbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-heart" {...props}></Icon>
