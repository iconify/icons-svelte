<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8b3c1bgc.css';
import '../../css/m/md2v-t2ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="d8b3c1bgc"/><path class="md2v-t2ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:norfolk-island" {...props}></Icon>
