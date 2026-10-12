<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti93n7b7m.css';
import '../../css/u/u2_dmwbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ti93n7b7m"/><path class="u2_dmwbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mouse-right-filled" {...props}></Icon>
