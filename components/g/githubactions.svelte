<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmqemt8zm.css';
import '../../css/k/katrf5x9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rmqemt8zm"/><path class="katrf5x9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:githubactions" {...props}></Icon>
