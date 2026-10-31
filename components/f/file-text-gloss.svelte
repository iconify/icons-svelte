<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8wj3rsvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8wj3rsvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-text-gloss" {...props}></Icon>
