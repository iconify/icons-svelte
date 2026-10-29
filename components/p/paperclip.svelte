<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx1mdyx4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx1mdyx4x wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:paperclip" {...props}></Icon>
