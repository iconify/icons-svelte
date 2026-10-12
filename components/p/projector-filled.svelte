<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6vzrquwp.css';
import '../../css/k/k_0sx3bjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c6vzrquwp"/><path class="k_0sx3bjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:projector-filled" {...props}></Icon>
