<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly_5izb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ly_5izb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:config-perl" {...props}></Icon>
