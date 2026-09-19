<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcpny1buv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rcpny1buv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:application" {...props}></Icon>
