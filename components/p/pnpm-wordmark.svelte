<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz4j5z9qi.css';
import '../../css/g/g878ilbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sz4j5z9qi"/><path class="g878ilbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:pnpm-wordmark" {...props}></Icon>
