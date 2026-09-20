<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t35nljbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t35nljbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:check-square-o" {...props}></Icon>
