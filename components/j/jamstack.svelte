<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t25chc-0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="t25chc-0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:jamstack" {...props}></Icon>
