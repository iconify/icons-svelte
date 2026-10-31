<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv3cqb9cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv3cqb9cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-minus-gloss" {...props}></Icon>
