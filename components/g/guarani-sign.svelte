<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk8pm6jyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="kk8pm6jyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:guarani-sign" {...props}></Icon>
