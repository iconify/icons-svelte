<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3jy0q-gs.css';
import '../../css/w/w_-a5y10p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3jy0q-gs"/><path class="w_-a5y10p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-search-filled" {...props}></Icon>
