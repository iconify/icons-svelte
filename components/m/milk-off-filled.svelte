<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-wy2pb_f.css';
import '../../css/b/bh7vv0tuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b-wy2pb_f"/><path class="bh7vv0tuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:milk-off-filled" {...props}></Icon>
