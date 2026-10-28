<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei1xe8bei.css';
import '../../css/i/i2eqxibtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ei1xe8bei"/><path class="i2eqxibtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:neon-wordmark" {...props}></Icon>
