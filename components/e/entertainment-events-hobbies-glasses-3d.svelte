<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1mc4j4if.css';
import '../../css/h/hg6am7bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g1mc4j4if"/><path class="hg6am7bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:entertainment-events-hobbies-glasses-3d" {...props}></Icon>
