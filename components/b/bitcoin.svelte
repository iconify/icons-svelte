<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef_mojbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ef_mojbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:bitcoin" {...props}></Icon>
