<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb-_2cc6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cb-_2cc6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:kos" {...props}></Icon>
