<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiof65b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hiof65b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:battery-medium-1-remix" {...props}></Icon>
