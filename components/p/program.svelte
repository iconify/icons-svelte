<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax6ykm6hi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ax6ykm6hi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:program" {...props}></Icon>
