<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9obxowyy.css';
import '../../css/n/n1rnmdo-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i9obxowyy"/><path class="n1rnmdo-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:award-20" {...props}></Icon>
