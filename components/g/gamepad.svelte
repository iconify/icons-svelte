<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0254uoqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":520,"height":448};
const content = `<path class="g0254uoqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:gamepad" {...props}></Icon>
