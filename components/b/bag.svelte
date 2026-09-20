<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr2sukbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kr2sukbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:bag" {...props}></Icon>
