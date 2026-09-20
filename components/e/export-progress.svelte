<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgm1g8b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mgm1g8b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:export-progress" {...props}></Icon>
