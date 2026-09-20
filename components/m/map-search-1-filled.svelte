<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_ihi-nli.css';
import '../../css/r/rb93hspbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_ihi-nli"/><path class="rb93hspbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-search-1-filled" {...props}></Icon>
