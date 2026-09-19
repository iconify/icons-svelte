<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_o-pw-1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z_o-pw-1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:caret-back-circle" {...props}></Icon>
