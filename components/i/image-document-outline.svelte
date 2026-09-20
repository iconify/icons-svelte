<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgehhybky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sgehhybky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:image-document-outline" {...props}></Icon>
