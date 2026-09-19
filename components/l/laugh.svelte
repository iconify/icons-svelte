<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh44u181c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="qh44u181c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:laugh" {...props}></Icon>
