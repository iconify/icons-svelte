<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abbf3ujbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="abbf3ujbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:euro" {...props}></Icon>
