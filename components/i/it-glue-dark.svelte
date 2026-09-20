<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtm8l_bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wtm8l_bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:it-glue-dark" {...props}></Icon>
