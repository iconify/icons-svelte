<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igog1ebsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="igog1ebsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eenvo-light" {...props}></Icon>
