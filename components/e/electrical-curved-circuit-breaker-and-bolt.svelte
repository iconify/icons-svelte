<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2c56nb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g2c56nb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:electrical-curved-circuit-breaker-and-bolt" {...props}></Icon>
