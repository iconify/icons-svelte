<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3667abak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h3667abak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:photorec" {...props}></Icon>
