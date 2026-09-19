<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afl_yub5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":832};
const content = `<path class="afl_yub5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:hdtv" {...props}></Icon>
