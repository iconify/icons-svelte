<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrkewab2c.css';
import '../../css/b/b7h45cb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="vrkewab2c"/><path class="b7h45cb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alternativeto" {...props}></Icon>
