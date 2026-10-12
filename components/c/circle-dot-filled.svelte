<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b39lfgb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b39lfgb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-dot-filled" {...props}></Icon>
