<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owvi75l7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="owvi75l7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:cake-slice-remix" {...props}></Icon>
