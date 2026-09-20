<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg9xpcbkq.css';
import '../../css/u/u-l7qbbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="lg9xpcbkq"/><path class="u-l7qbbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-infectious-diseases" {...props}></Icon>
