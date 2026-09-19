<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd6c9-4-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd6c9-4-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:file-image" {...props}></Icon>
