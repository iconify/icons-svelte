<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xejap0mig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xejap0mig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:certificate-success" {...props}></Icon>
