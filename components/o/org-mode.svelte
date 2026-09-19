<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgznimbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":467,"height":512};
const content = `<path class="hgznimbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:org-mode" {...props}></Icon>
