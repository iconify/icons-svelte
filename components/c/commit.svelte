<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obyh4cyrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="obyh4cyrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:commit" {...props}></Icon>
