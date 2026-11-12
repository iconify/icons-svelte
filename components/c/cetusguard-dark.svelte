<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnosqrbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jnosqrbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cetusguard-dark" {...props}></Icon>
