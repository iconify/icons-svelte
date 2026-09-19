<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjhyc3iad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hjhyc3iad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:cardano" {...props}></Icon>
