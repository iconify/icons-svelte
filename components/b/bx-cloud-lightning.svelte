<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0vzs5apr.css';
import '../../css/t/toc-9jzis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0vzs5apr"/><path class="toc-9jzis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-cloud-lightning" {...props}></Icon>
