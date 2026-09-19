<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyb2rnbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eyb2rnbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:code-hide" {...props}></Icon>
