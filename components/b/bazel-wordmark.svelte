<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqs3_17lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jqs3_17lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:bazel-wordmark" {...props}></Icon>
