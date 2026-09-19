<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8t4m96uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":435,"height":512};
const content = `<path class="k8t4m96uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:libuv" {...props}></Icon>
