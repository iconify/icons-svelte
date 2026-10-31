<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxr7riqlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxr7riqlp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:book-fill-round" {...props}></Icon>
