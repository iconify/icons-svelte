<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahdyb5byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ahdyb5byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:infisical-dark" {...props}></Icon>
