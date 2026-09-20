<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf53md_sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="hf53md_sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-up-right-fill" {...props}></Icon>
