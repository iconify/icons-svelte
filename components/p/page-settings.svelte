<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aerf2dljn.css';
import '../../css/p/p27qq8biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aerf2dljn"/><path class="p27qq8biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:page-settings" {...props}></Icon>
