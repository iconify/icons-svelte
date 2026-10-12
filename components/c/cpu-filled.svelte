<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3jnswbyn.css';
import '../../css/n/n3b-hhblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3jnswbyn"/><path clip-rule="evenodd" class="n3b-hhblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cpu-filled" {...props}></Icon>
