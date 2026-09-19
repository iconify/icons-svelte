<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6m7-ac3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6m7-ac3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-99designs" {...props}></Icon>
