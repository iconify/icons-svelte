<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3_gtob6t.css';
import '../../css/p/p9-9dkipc.css';
import '../../css/u/u4839bbhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3_gtob6t"/><path class="p9-9dkipc"/><path clip-rule="evenodd" class="u4839bbhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:library-bold" {...props}></Icon>
