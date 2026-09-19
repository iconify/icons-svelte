<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrb8hk_en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qrb8hk_en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-video" {...props}></Icon>
