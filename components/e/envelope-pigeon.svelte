<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohbffsb_w.css';
import '../../css/t/tj55anbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohbffsb_w"/><path class="tj55anbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:envelope-pigeon" {...props}></Icon>
