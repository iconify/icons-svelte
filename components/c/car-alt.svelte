<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_ri79bak.css';
import '../../css/s/sl-mdjb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="w_ri79bak"/><path class="sl-mdjb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:car-alt" {...props}></Icon>
