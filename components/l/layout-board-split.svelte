<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll_87xwpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ll_87xwpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-board-split" {...props}></Icon>
