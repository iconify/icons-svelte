<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7gie67ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":52,"height":28};
const content = `<path clip-rule="evenodd" class="s7gie67ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cisco-light" {...props}></Icon>
