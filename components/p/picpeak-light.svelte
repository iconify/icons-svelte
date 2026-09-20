<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igxlhbcep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="igxlhbcep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:picpeak-light" {...props}></Icon>
