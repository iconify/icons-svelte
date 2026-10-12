<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozxylewza.css';
import '../../css/z/ztl9t8bet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozxylewza"/><path clip-rule="evenodd" class="ztl9t8bet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-gauge-filled" {...props}></Icon>
