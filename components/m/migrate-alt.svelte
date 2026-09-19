<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrw6p6brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jrw6p6brg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:migrate-alt" {...props}></Icon>
