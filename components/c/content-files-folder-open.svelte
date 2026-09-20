<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsldmpb3s.css';
import '../../css/f/f9o_g2bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xsldmpb3s"/><path class="f9o_g2bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:content-files-folder-open" {...props}></Icon>
