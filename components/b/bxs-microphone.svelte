<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl7t8bcmf.css';
import '../../css/y/yzdqdzd3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl7t8bcmf"/><path class="yzdqdzd3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-microphone" {...props}></Icon>
