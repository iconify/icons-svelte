<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3qs2xnju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l3qs2xnju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crossed-air-flows" {...props}></Icon>
