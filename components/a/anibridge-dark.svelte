<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zamm8q_ux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zamm8q_ux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:anibridge-dark" {...props}></Icon>
