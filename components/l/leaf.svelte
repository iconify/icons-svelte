<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji7elbcuq.css';
import '../../css/n/ne0cv4kxd.css';
import '../../css/x/xd30uik4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ji7elbcuq wm-k"/><path class="ne0cv4kxd wm-k"/><path class="wm-a xd30uik4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:leaf" {...props}></Icon>
