<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6g6chb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c6g6chb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:matrix" {...props}></Icon>
