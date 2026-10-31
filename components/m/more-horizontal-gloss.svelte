<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb0yovfwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb0yovfwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:more-horizontal-gloss" {...props}></Icon>
