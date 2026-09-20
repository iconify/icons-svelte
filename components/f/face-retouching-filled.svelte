<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdjuwtb7o.css';
import '../../css/r/r-t90pbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdjuwtb7o"/><path class="r-t90pbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:face-retouching-filled" {...props}></Icon>
