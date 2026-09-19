<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5uqnmb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":425,"height":512};
const content = `<path class="g5uqnmb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:platformio" {...props}></Icon>
