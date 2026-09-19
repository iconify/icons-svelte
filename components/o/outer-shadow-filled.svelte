<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_tahrbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b d_tahrbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:outer-shadow-filled" {...props}></Icon>
