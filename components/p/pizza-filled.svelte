<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuf07w3fy.css';
import '../../css/j/jnfkx1eag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zuf07w3fy"/><path class="jnfkx1eag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pizza-filled" {...props}></Icon>
