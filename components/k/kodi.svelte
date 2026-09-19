<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvhfc9blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvhfc9blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:kodi" {...props}></Icon>
