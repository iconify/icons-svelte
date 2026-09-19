<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljykc90oq.css';
import '../../css/i/ivll_4uwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljykc90oq"/><path class="ivll_4uwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bullseye" {...props}></Icon>
