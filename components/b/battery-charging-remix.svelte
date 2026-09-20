<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sba806y6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sba806y6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:battery-charging-remix" {...props}></Icon>
