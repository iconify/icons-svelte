<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvp6zsbrb.css';
import '../../css/b/bv-ekvb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvp6zsbrb"/><path class="bv-ekvb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:finger-swipe-up" {...props}></Icon>
