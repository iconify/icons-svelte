<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nglbulbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nglbulbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:polaroid-four-solid" {...props}></Icon>
