<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0skt9b0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o0skt9b0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:end-point-diamond-flat" {...props}></Icon>
