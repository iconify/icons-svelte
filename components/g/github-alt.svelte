<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlznm7l6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="zlznm7l6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:github-alt" {...props}></Icon>
