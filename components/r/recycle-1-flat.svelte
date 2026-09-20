<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvu0--6-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bvu0--6-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:recycle-1-flat" {...props}></Icon>
