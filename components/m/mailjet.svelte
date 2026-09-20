<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujux3-pap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ujux3-pap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailjet" {...props}></Icon>
