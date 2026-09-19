<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di-eyczor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="di-eyczor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:hand-draw-fill" {...props}></Icon>
