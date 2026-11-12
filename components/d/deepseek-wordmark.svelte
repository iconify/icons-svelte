<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv1wov0db.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pv1wov0db"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:deepseek-wordmark" {...props}></Icon>
