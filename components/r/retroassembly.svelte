<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx7mr1bdl.css';
import '../../css/z/zp52ksh9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="wx7mr1bdl"/><path class="zp52ksh9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:retroassembly" {...props}></Icon>
