<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azc5oubyv.css';
import '../../css/y/ywfl4rbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="azc5oubyv"/><path class="ywfl4rbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuel-pump-20-bold" {...props}></Icon>
