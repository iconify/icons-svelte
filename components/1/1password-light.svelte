<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7b6kibir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l7b6kibir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:1password-light" {...props}></Icon>
