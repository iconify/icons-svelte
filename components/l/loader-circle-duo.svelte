<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx2uz1-fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx2uz1-fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:loader-circle-duo" {...props}></Icon>
