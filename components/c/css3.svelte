<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5y6pnb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q5y6pnb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:css3" {...props}></Icon>
