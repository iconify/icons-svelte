<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co2lme0xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="co2lme0xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hook0-dark" {...props}></Icon>
