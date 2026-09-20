<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scf1s7c6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="scf1s7c6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:left-click-remix" {...props}></Icon>
