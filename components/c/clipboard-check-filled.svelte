<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu20g6b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu20g6b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clipboard-check-filled" {...props}></Icon>
