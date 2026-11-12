<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr-iiqyqg.css';
import '../../css/f/f6p_znbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rr-iiqyqg"/><path class="f6p_znbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bracket-dark" {...props}></Icon>
