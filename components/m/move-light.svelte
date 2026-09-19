<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b21075lxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b21075lxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:move-light" {...props}></Icon>
