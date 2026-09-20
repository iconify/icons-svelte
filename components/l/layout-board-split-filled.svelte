<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppclbl6nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppclbl6nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-board-split-filled" {...props}></Icon>
