<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7uym8gtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y7uym8gtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:less-than-sign-circle-solid" {...props}></Icon>
