<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgy32l41g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qgy32l41g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:qtest-wordmark" {...props}></Icon>
