<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz5qx46vr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cz5qx46vr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:flash-3-remix" {...props}></Icon>
