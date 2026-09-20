<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt7j6mbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt7j6mbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:file" {...props}></Icon>
