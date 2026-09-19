<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfiw6xiub.css';
import '../../css/o/oitaj0ijo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zfiw6xiub"/><path class="oitaj0ijo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:condition-wait-point" {...props}></Icon>
