<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4a006b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="g4a006b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:projector-board" {...props}></Icon>
