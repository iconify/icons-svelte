<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iht9-obua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iht9-obua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:credit-card-minus" {...props}></Icon>
