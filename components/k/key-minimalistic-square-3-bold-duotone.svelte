<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/g/gsvy13bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path clip-rule="evenodd" class="gsvy13bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:key-minimalistic-square-3-bold-duotone" {...props}></Icon>
