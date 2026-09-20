<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwxwddxbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":200,"height":171};
const content = `<path class="kwxwddxbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kvant-system" {...props}></Icon>
