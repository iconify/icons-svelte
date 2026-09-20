<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfrefdafx.css';
import '../../css/c/cion4p3li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gfrefdafx"/><path class="cion4p3li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fmd-dark" {...props}></Icon>
