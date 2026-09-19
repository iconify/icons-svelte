<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypv2wabxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ypv2wabxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:align-horizontal-center-two" {...props}></Icon>
