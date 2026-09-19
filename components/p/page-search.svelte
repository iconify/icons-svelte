<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwm_4jb1w.css';
import '../../css/j/jmbrci4fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="qwm_4jb1w"/><path class="jmbrci4fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:page-search" {...props}></Icon>
