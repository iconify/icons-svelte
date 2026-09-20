<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx_0ltekc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bx_0ltekc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-upload-fill" {...props}></Icon>
