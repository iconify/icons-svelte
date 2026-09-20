<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-29-dopm.css';
import '../../css/o/okgd0ab2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<rect class="z-29-dopm"/><path class="okgd0ab2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:huff-light" {...props}></Icon>
