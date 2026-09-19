<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf-wdxbtk.css';
import '../../css/k/krz3t3bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rf-wdxbtk"/><path class="krz3t3bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:remove" {...props}></Icon>
