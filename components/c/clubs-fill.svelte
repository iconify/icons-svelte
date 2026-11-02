<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_32m667j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_32m667j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clubs-fill" {...props}></Icon>
