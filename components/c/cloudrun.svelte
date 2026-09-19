<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm-bnc59e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hm-bnc59e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:cloudrun" {...props}></Icon>
