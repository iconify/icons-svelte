<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6pehnbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j6pehnbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:moocup-dark" {...props}></Icon>
