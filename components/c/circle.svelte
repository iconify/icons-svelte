<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgl32slbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jgl32slbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:circle" {...props}></Icon>
