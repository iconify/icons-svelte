<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3k-rut9k.css';
import '../../css/v/val4s82hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="g3k-rut9k"/><path class="val4s82hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:accent" {...props}></Icon>
