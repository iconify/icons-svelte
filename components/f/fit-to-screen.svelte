<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aucqcrb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aucqcrb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:fit-to-screen" {...props}></Icon>
