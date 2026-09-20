<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e__73ozkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e__73ozkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrows-left-right-above-water" {...props}></Icon>
