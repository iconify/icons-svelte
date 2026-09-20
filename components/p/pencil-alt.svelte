<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj1embc0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="xj1embc0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pencil-alt" {...props}></Icon>
