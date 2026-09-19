<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z950rcxpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z950rcxpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-font-fill" {...props}></Icon>
