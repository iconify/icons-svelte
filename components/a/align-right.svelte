<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd4exubgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="nd4exubgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:align-right" {...props}></Icon>
