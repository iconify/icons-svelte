<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dganpjjey.css';
import '../../css/f/fna3t83oh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dganpjjey"/><path class="fna3t83oh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:javascript" {...props}></Icon>
