<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/k/kf84qox3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path clip-rule="evenodd" class="kf84qox3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:key-minimalistic-square-2-bold-duotone" {...props}></Icon>
