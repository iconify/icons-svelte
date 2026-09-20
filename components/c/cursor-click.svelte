<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytzi4p-xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ytzi4p-xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:cursor-click" {...props}></Icon>
