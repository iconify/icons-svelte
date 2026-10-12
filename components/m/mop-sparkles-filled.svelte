<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh4-yy1bi.css';
import '../../css/j/jnfyn9bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fh4-yy1bi"/><path class="jnfyn9bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mop-sparkles-filled" {...props}></Icon>
