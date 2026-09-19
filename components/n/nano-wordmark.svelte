<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_xs-qb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q_xs-qb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nano-wordmark" {...props}></Icon>
