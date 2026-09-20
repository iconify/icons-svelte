<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxjsu19re.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vxjsu19re"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:folder" {...props}></Icon>
