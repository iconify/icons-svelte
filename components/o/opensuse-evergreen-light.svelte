<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8oe4bcvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8oe4bcvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opensuse-evergreen-light" {...props}></Icon>
