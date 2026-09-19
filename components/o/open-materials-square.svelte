<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q69k124zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="q69k124zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:open-materials-square" {...props}></Icon>
