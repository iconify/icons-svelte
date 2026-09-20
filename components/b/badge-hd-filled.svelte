<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrjkswdhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrjkswdhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:badge-hd-filled" {...props}></Icon>
