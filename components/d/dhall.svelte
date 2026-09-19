<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el0u0wbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":243,"height":512};
const content = `<path class="el0u0wbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:dhall" {...props}></Icon>
