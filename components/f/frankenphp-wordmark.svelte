<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7rn45-1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="u7rn45-1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:frankenphp-wordmark" {...props}></Icon>
