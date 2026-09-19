<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt6plcbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":832,"height":1024};
const content = `<path class="bt6plcbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:punisher" {...props}></Icon>
