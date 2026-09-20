<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj3p5qbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kj3p5qbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:citibank-dark" {...props}></Icon>
