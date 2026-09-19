<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv29rccow.css';
import '../../css/y/yz7t0mb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer iv29rccow"/><path class="duoicon-primary-layer yz7t0mb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:rocket" {...props}></Icon>
