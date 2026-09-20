<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnw-p-byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnw-p-byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-alt-upload" {...props}></Icon>
