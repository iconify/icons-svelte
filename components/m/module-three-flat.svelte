<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjqj978si.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kjqj978si"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:module-three-flat" {...props}></Icon>
