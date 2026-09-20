<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5jsw1_0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v5jsw1_0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:beach-remix" {...props}></Icon>
