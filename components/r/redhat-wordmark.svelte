<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8yzh57pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="g8yzh57pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:redhat-wordmark" {...props}></Icon>
