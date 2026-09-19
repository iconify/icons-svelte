<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocd8hrmmu.css';
import '../../css/q/qosfk73sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ocd8hrmmu"/><path class="qosfk73sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:factory" {...props}></Icon>
