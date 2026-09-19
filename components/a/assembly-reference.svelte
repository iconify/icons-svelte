<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w571e2b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w571e2b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:assembly-reference" {...props}></Icon>
