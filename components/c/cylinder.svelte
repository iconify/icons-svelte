<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbxnn8bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jbxnn8bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cylinder" {...props}></Icon>
