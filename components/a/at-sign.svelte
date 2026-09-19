<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kio30xvjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="kio30xvjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:at-sign" {...props}></Icon>
