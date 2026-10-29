<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0h540-ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0h540-ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:lamp-desk" {...props}></Icon>
