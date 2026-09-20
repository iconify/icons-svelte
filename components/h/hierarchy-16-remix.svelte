<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnq2fg_cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xnq2fg_cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:hierarchy-16-remix" {...props}></Icon>
