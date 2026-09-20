<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oot5ivbbj.css';
import '../../css/n/n3wlgc-qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oot5ivbbj"/><path class="n3wlgc-qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:content-files-pdf" {...props}></Icon>
