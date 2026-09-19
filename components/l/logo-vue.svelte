<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exv3ojb0v.css';
import '../../css/s/sdocp_b4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="exv3ojb0v"/><path class="sdocp_b4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-vue" {...props}></Icon>
