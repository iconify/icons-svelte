<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igfbz1bed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="igfbz1bed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:prescription-bottle-medical" {...props}></Icon>
