<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okmjdzbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="okmjdzbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:list" {...props}></Icon>
