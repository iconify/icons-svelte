<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdr87f6cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gdr87f6cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:downward" {...props}></Icon>
