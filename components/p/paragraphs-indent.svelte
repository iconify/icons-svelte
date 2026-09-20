<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er0e4cwyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="er0e4cwyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:paragraphs-indent" {...props}></Icon>
