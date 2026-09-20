<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc82nbjiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gc82nbjiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:grid-lock-filled" {...props}></Icon>
