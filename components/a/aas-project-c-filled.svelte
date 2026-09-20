<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt1f1hbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vt1f1hbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-project-c-filled" {...props}></Icon>
