<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2pq0ccjr.css';
import '../../css/d/di12r_hgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2pq0ccjr"/><path class="di12r_hgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pizza-alt" {...props}></Icon>
