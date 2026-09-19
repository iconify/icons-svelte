<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye-mnojip.css';
import '../../css/i/i69vb9b6y.css';
import '../../css/i/i8ac7e7vw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ye-mnojip"/><circle class="i69vb9b6y"/><path class="i8ac7e7vw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:bike" {...props}></Icon>
