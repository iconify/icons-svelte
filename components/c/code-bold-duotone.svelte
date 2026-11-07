<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2emkyb0z.css';
import '../../css/e/eg843s-3q.css';
import '../../css/b/bm7srd-6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2emkyb0z"/><path class="eg843s-3q"/><path class="bm7srd-6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-bold-duotone" {...props}></Icon>
