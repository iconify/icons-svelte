<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpj6p9orf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":875,"height":2048};
const content = `<path class="tpj6p9orf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:right-double-quote" {...props}></Icon>
