<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl0vbpbky.css';
import '../../css/x/xq0giqbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gl0vbpbky"/><path class="xq0giqbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:comment-alt-plus" {...props}></Icon>
