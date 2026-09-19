<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8z5myb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s8z5myb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:mjml" {...props}></Icon>
