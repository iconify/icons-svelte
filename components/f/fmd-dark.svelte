<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfrefdafx.css';
import '../../css/a/a4aiwucjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gfrefdafx"/><path class="a4aiwucjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fmd-dark" {...props}></Icon>
