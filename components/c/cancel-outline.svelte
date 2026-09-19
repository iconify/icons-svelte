<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol05o0b3n.css';
import '../../css/b/buewkbcgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol05o0b3n"/><path clip-rule="evenodd" class="buewkbcgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:cancel-outline" {...props}></Icon>
