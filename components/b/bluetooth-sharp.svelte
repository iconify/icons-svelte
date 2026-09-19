<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3q3w37ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a3q3w37ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bluetooth-sharp" {...props}></Icon>
