<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qln3eyb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qln3eyb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nit" {...props}></Icon>
