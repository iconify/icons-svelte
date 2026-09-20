<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8u1chjgn.css';
import '../../css/x/xl35czbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8u1chjgn"/><path class="xl35czbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:comment-2-fill" {...props}></Icon>
