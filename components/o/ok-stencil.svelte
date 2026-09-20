<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df7-84bmu.css';
import '../../css/w/whpncgbes.css';
import '../../css/l/lbxg3kb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="df7-84bmu"/><path class="whpncgbes"/><path class="lbxg3kb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:ok-stencil" {...props}></Icon>
