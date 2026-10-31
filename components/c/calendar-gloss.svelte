<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b94hs4mrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b94hs4mrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calendar-gloss" {...props}></Icon>
