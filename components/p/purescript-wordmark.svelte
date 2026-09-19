<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qghqrkb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qghqrkb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:purescript-wordmark" {...props}></Icon>
