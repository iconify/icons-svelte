<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea-d-nbfx.css';
import '../../css/j/jjn413bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ea-d-nbfx"/><path class="jjn413bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:jersey-20-bold" {...props}></Icon>
