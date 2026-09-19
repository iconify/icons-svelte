<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m58734bmb.css';
import '../../css/b/b3dakxwyz.css';
import '../../css/n/n8ps1yhvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="m58734bmb"/><path class="b3dakxwyz"/><path class="n8ps1yhvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:leetcode-wordmark" {...props}></Icon>
