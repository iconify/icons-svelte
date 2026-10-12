<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amszec7ov.css';
import '../../css/r/roxo8uutm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="amszec7ov"/><path class="roxo8uutm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-double-right-20" {...props}></Icon>
