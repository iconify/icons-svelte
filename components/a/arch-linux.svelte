<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeqxqxbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qeqxqxbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:arch-linux" {...props}></Icon>
