<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/w/wg3spykob.css';
import '../../css/v/vdnlq5aee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="wg3spykob"/><path class="vdnlq5aee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:comment-dots-bold" {...props}></Icon>
