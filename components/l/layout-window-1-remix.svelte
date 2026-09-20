<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_l_2rugl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f_l_2rugl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:layout-window-1-remix" {...props}></Icon>
