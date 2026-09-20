<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsy1fdcdi.css';
import '../../css/c/cy43ccb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsy1fdcdi"/><path clip-rule="evenodd" class="cy43ccb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bld" {...props}></Icon>
