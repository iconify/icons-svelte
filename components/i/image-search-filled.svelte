<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aznt7d64g.css';
import '../../css/l/ld_h86szq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aznt7d64g"/><path class="ld_h86szq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:image-search-filled" {...props}></Icon>
