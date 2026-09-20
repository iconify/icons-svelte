<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrb6h1bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrb6h1bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:injective" {...props}></Icon>
