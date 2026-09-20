<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx1csacef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tx1csacef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:line" {...props}></Icon>
