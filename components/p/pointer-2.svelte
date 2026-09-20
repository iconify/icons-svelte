<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9p2uebrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9p2uebrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pointer-2" {...props}></Icon>
