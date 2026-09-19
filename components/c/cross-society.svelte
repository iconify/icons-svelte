<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jddr2hbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jddr2hbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cross-society" {...props}></Icon>
