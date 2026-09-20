<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oolt7f-px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oolt7f-px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:cyborg-2-solid" {...props}></Icon>
