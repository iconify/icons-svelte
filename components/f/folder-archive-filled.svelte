<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xckdb_rmw.css';
import '../../css/d/dau5oxg5b.css';
import '../../css/y/yufc7rbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xckdb_rmw"/><path class="dau5oxg5b"/><path class="yufc7rbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-archive-filled" {...props}></Icon>
