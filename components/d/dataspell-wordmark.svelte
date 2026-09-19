<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jet9moexx.css';
import '../../css/k/knjswsrwz.css';
import '../../css/b/bql6r7x-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jet9moexx"/><path class="knjswsrwz"/><path class="bql6r7x-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:dataspell-wordmark" {...props}></Icon>
