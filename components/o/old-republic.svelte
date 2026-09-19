<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4lyu_g1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="e4lyu_g1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:old-republic" {...props}></Icon>
