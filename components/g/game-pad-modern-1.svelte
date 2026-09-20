<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z96yl-b9i.css';
import '../../css/a/ad7wyubda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z96yl-b9i"/><path clip-rule="evenodd" class="ad7wyubda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:game-pad-modern-1" {...props}></Icon>
