<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqo-n47ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="rqo-n47ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:grow" {...props}></Icon>
