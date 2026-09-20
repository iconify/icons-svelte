<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knuwu50tq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knuwu50tq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pointer-search" {...props}></Icon>
