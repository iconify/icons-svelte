<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbv0mj7_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="tbv0mj7_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:file-upload" {...props}></Icon>
