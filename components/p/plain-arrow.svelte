<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgz_b5v2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qgz_b5v2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:plain-arrow" {...props}></Icon>
