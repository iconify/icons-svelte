<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaxt6_bwl.css';
import '../../css/x/x4jziszvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jaxt6_bwl"/><path class="x4jziszvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:character-integer" {...props}></Icon>
