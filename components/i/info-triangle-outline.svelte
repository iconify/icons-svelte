<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afl8jx6mv.css';
import '../../css/u/u4xq7tb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afl8jx6mv"/><path clip-rule="evenodd" class="u4xq7tb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:info-triangle-outline" {...props}></Icon>
