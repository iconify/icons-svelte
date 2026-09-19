<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvr2fkdlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dvr2fkdlw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:fourleafclover" {...props}></Icon>
