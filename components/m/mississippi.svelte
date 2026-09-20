<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5xx76bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t5xx76bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mississippi" {...props}></Icon>
