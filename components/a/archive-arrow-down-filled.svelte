<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv_zv7bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv_zv7bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:archive-arrow-down-filled" {...props}></Icon>
