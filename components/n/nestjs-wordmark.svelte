<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmw9lxb9g.css';
import '../../css/n/n8mc1xbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pmw9lxb9g"/><path class="n8mc1xbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nestjs-wordmark" {...props}></Icon>
