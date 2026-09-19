<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pth79ynrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pth79ynrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:hipchat" {...props}></Icon>
