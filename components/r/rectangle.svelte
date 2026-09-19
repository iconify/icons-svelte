<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzy-83atc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jzy-83atc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:rectangle" {...props}></Icon>
