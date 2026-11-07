<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln-hxshjc.css';
import '../../css/o/oiqop8ebf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ln-hxshjc"/><path class="oiqop8ebf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-2x2-close-outline" {...props}></Icon>
