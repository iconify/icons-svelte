<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8bm8_bmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r8bm8_bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:polaroid" {...props}></Icon>
