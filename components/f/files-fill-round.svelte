<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy5i8ob_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy5i8ob_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:files-fill-round" {...props}></Icon>
