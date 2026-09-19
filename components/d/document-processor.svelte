<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef8a_j6zj.css';
import '../../css/r/rxpq2xbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ef8a_j6zj"/><path class="rxpq2xbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-processor" {...props}></Icon>
