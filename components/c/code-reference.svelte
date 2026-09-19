<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6sj14czw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r6sj14czw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:code-reference" {...props}></Icon>
