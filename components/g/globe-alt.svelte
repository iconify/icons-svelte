<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhu29pbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jhu29pbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:globe-alt" {...props}></Icon>
