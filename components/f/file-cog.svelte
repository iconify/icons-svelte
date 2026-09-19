<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixwkb7bem.css';
import '../../css/a/aie3xzkwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixwkb7bem"/><path class="aie3xzkwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-cog" {...props}></Icon>
