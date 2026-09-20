<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn3g53b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rn3g53b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:file-addition" {...props}></Icon>
