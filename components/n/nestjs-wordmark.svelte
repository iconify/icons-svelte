<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srb547bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="srb547bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nestjs-wordmark" {...props}></Icon>
