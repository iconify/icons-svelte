<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv1zt7bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hv1zt7bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:new-badge-highlight-remix" {...props}></Icon>
