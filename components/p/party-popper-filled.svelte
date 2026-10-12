<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m71bvmvxt.css';
import '../../css/j/ju3sbspwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m71bvmvxt"/><path class="ju3sbspwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:party-popper-filled" {...props}></Icon>
