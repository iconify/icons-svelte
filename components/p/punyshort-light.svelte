<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc6r_1jfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jc6r_1jfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:punyshort-light" {...props}></Icon>
