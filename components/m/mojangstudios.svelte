<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydiwi1btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydiwi1btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:mojangstudios" {...props}></Icon>
