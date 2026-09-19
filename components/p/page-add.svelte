<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lots55p-n.css';
import '../../css/p/psm-cjbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="lots55p-n"/><path class="psm-cjbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:page-add" {...props}></Icon>
