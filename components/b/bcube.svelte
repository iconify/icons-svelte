<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grfwzfblc.css';
import '../../css/u/uszi3vbgi.css';
import '../../css/j/j3bk5ybiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grfwzfblc"/><path class="uszi3vbgi"/><path clip-rule="evenodd" class="j3bk5ybiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bcube" {...props}></Icon>
