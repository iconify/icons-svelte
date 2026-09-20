<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itq-opb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="itq-opb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:arrowright2" {...props}></Icon>
