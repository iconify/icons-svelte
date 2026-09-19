<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oue1_lxyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oue1_lxyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:hackaday" {...props}></Icon>
