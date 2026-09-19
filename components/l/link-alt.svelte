<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si-zo371a.css';
import '../../css/r/rpw047bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="si-zo371a"/><path class="rpw047bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:link-alt" {...props}></Icon>
